<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kwvz9gbdr.css';
import '../../css/x/xf1rtpbyd.css';
import '../../css/m/mqc3cacsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kwvz9gbdr"/><path class="xf1rtpbyd"/><path class="mqc3cacsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:blend-duotone" /></template>
