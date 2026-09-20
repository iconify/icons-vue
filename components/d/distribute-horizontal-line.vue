<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/sxqx-5kxh.css';
import '../../css/p/p5b6m0brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sxqx-5kxh"/><rect transform="rotate(-90 10 17)" class="p5b6m0brr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:distribute-horizontal-line" /></template>
