<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/szduz5tno.css';
import '../../css/u/uub3otbcq.css';
import '../../css/k/k9i0_pbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="szduz5tno"/><path class="uub3otbcq"/><path class="k9i0_pbrn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:film-1" /></template>
