<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8jxl3bzb.css';
import '../../css/b/bqmve1p5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="w8jxl3bzb"/><path class="bqmve1p5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:heavy-dollar-sign" /></template>
