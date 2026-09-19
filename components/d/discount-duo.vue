<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r8yxl582h.css';
import '../../css/r/rvcv5yw0j.css';
import '../../css/t/tzdbdn7ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="r8yxl582h"/><path class="rvcv5yw0j"/><path class="tzdbdn7ho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:discount-duo" /></template>
