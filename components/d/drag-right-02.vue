<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/etrfmvbak.css';
import '../../css/g/gsjdp6b8k.css';
import '../../css/n/n6qk4ubzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="etrfmvbak"/><path class="gsjdp6b8k"/><path class="n6qk4ubzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:drag-right-02" /></template>
