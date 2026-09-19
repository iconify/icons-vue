<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgh857k-g.css';
import '../../css/h/hgpzimtyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wgh857k-g"/><path class="hgpzimtyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-high-low" /></template>
