<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/p/pjl1_rn1g.css';
import '../../css/s/ssdrdhlvc.css';
import '../../css/l/l9j2af_qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="pjl1_rn1g"/><path class="ssdrdhlvc"/><path class="l9j2af_qv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:bus" /></template>
