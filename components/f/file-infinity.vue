<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/l72ym8u0j.css';
import '../../css/f/fwo4s-hri.css';
import '../../css/t/t_3o8abnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l72ym8u0j"/><path class="fwo4s-hri"/><path class="t_3o8abnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:file-infinity" /></template>
