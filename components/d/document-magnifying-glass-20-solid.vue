<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x1x_shbfr.css';
import '../../css/h/hrclzsfpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="x1x_shbfr"/><path clip-rule="evenodd" class="hrclzsfpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-magnifying-glass-20-solid" /></template>
