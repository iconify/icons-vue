<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_d1t5cfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e_d1t5cfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:italic-arab-keheh-jeem" /></template>
