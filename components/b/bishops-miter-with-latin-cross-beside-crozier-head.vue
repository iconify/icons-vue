<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp7mpy2fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lp7mpy2fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bishops-miter-with-latin-cross-beside-crozier-head" /></template>
