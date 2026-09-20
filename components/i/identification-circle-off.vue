<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h36sa31ok.css';
import '../../css/q/qwsb0-m-k.css';
import '../../css/q/q3d0nnoea.css';
import '../../css/i/i2r9qrcoy.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="h36sa31ok"/><path clip-rule="evenodd" class="qwsb0-m-k"/><path class="q3d0nnoea"/><path class="i2r9qrcoy"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:identification-circle-off" /></template>
