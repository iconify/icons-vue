<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/efb2s37wt.css';
import '../../css/o/ocyd4bb0x.css';
import '../../css/p/piya6qlkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="efb2s37wt"/><path class="ocyd4bb0x"/><path class="piya6qlkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cloudy-mostly-outline" /></template>
