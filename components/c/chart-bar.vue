<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vbriv1mcf.css';
import '../../css/x/xahsavp3d.css';
import '../../css/z/z_9naomrb.css';
import '../../css/n/n1-j0_bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="vbriv1mcf"/><path clip-rule="evenodd" class="xahsavp3d"/><path clip-rule="evenodd" class="z_9naomrb"/><path class="n1-j0_bve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:chart-bar" /></template>
