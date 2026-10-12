<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oxrgvbcdf.css';
import '../../css/r/rt3fdztit.css';
import '../../css/n/n59n-mb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oxrgvbcdf"/><path class="rt3fdztit"/><path class="n59n-mb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layers-plus-duotone" /></template>
