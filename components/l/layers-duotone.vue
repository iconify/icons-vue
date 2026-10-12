<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oxrgvbcdf.css';
import '../../css/r/rt3fdztit.css';
import '../../css/w/w6mpc9bne.css';
import '../../css/q/qnyh8hkdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oxrgvbcdf"/><path class="rt3fdztit"/><path class="w6mpc9bne"/><path class="qnyh8hkdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layers-duotone" /></template>
