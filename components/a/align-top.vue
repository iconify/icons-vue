<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zf63p2uya.css';
import '../../css/o/o5x-6cbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><rect transform="matrix(1 0 0 -1 6 15)" class="zf63p2uya"/><path class="o5x-6cbab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:align-top" /></template>
