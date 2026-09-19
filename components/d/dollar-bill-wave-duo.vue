<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lyxil9baw.css';
import '../../css/t/tylp8-t1y.css';
import '../../css/y/y_ry23blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lyxil9baw"/><path class="tylp8-t1y"/><path class="y_ry23blx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:dollar-bill-wave-duo" /></template>
