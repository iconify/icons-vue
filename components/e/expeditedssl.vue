<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9b1ifivl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="a9b1ifivl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:expeditedssl" /></template>
