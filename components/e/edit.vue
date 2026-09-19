<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/le33hqf6m.css';
import '../../css/w/wz94lmb_y.css';
import '../../css/o/o57o9vpnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="le33hqf6m"/><path clip-rule="evenodd" class="wz94lmb_y"/><path class="o57o9vpnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:edit" /></template>
