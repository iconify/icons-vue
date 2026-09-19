<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2112k_vg.css';
import '../../css/y/y2nmqhmom.css';
import '../../css/g/gdrmk4bfv.css';
import '../../css/s/smfv_omyd.css';
import '../../css/y/yrwibac8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r2112k_vg"/><path class="y2nmqhmom"/><path class="gdrmk4bfv"/><path class="smfv_omyd"/><path class="yrwibac8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:huoshanzhibo" /></template>
