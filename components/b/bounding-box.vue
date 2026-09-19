<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpocgmcex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cpocgmcex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bounding-box" /></template>
