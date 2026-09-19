<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jayab4bkc.css';
import '../../css/l/looxvfs3b.css';
import '../../css/l/loy_czb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="jayab4bkc"/><path class="looxvfs3b"/><path class="loy_czb3p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-half-2-bold" /></template>
