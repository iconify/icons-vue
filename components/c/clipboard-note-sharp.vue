<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f41ybed1i.css';
import '../../css/m/m1x4wtgmy.css';
import '../../css/f/f9d6qcb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f41ybed1i"/><path class="m1x4wtgmy"/><path class="f9d6qcb-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:clipboard-note-sharp" /></template>
