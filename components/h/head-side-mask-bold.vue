<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/en4wdebxd.css';
import '../../css/f/fux_uqjfv.css';
import '../../css/i/i_ug-dbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="en4wdebxd"/><path class="fux_uqjfv"/><path class="i_ug-dbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:head-side-mask-bold" /></template>
