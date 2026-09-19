<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tu9zc4bos.css';
import '../../css/x/xzt97hidt.css';
import '../../css/u/u8d4vrbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tu9zc4bos"/><path class="xzt97hidt"/><path class="u8d4vrbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:dislike-duotone" /></template>
