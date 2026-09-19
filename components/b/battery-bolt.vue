<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tr6gbxluw.css';
import '../../css/k/knq1obbqm.css';
import '../../css/r/rlafmm9-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="tr6gbxluw"/><path clip-rule="evenodd" class="knq1obbqm"/><path class="rlafmm9-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:battery-bolt" /></template>
