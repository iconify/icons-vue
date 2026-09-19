<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9ga7w1cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="e9ga7w1cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:fedex" /></template>
