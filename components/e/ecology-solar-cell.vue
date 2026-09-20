<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0s-mkc2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y0s-mkc2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:ecology-solar-cell" /></template>
