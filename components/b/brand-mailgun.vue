<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld24yvbps.css';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/fbh-igbpy.css';
import '../../css/o/o1z2wccdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGSD8t0Sim" class="ld24yvbps"/></defs><g class="nrj6p8qat"><path class="fbh-igbpy"/><path class="o1z2wccdo"/><use href="#SVGSD8t0Sim"/><use href="#SVGSD8t0Sim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-mailgun" /></template>
