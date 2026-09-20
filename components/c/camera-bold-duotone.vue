<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mw2j0bfon.css';
import '../../css/c/crk1mub_d.css';
import '../../css/s/shkc45brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mw2j0bfon"/><path class="crk1mub_d"/><path clip-rule="evenodd" class="shkc45brf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-bold-duotone" /></template>
