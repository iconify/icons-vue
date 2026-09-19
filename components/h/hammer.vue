<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qq-kuu89s.css';
import '../../css/f/fmlvbub9w.css';
import '../../css/u/u2_g62bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="qq-kuu89s"/><path clip-rule="evenodd" class="fmlvbub9w"/><path class="u2_g62bcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:hammer" /></template>
