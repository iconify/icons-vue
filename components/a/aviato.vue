<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fypl5kbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fypl5kbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:aviato" /></template>
