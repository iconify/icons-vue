<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/x06t6zbqg.css';
import '../../css/m/mw42pob4d.css';
import '../../css/p/pqorf1bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x06t6zbqg"/><path class="mw42pob4d"/><path class="pqorf1bzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-music-line-duotone" /></template>
