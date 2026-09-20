<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c6aatbbnu.css';
import '../../css/p/pqx2-oyar.css';
import '../../css/l/l4vllvb7o.css';
import '../../css/t/tnwts_9gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c6aatbbnu"/><path class="pqx2-oyar"/><path class="l4vllvb7o"/><path class="tnwts_9gl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-check-minimalistic-broken" /></template>
