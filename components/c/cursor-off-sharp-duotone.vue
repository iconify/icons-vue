<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/f/fduz3ccfo.css';
import '../../css/v/v5ezk3k3l.css';
import '../../css/k/km1bwubkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fduz3ccfo"/><path class="v5ezk3k3l"/><path class="km1bwubkj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-off-sharp-duotone" /></template>
