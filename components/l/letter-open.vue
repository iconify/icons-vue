<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pa_9qdbec.css';
import '../../css/l/lscdjjb2c.css';
import '../../css/l/lix8x_bop.css';
import '../../css/g/g5j1c6bbx.css';
import '../../css/j/jnouqxjlv.css';
import '../../css/f/ffnmybcie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="pa_9qdbec"/><path class="lscdjjb2c"/><path class="lix8x_bop"/><path clip-rule="evenodd" class="g5j1c6bbx"/><path clip-rule="evenodd" class="jnouqxjlv"/><path clip-rule="evenodd" class="ffnmybcie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:letter-open" /></template>
