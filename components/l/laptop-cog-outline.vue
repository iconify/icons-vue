<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/knrnv_33u.css';
import '../../css/u/ub4lowbdm.css';
import '../../css/t/tb6awyqzo.css';
import '../../css/z/z9c2rqbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="knrnv_33u"/><path clip-rule="evenodd" class="ub4lowbdm"/><path clip-rule="evenodd" class="tb6awyqzo"/><path class="z9c2rqbly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:laptop-cog-outline" /></template>
