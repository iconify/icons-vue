<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/j/j5as4w8rp.css';
import '../../css/q/qnba0sb7c.css';
import '../../css/z/zvs88eytg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j5as4w8rp"/><path class="qnba0sb7c"/><path class="zvs88eytg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-off-sharp-two-tone" /></template>
