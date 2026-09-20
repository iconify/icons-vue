<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iqj065bgh.css';
import '../../css/b/b3lwj2bjo.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="iqj065bgh"/><path clip-rule="evenodd" class="b3lwj2bjo"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:flower-bud-off" /></template>
