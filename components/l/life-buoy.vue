<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/u/uhxia1b7z.css';
import '../../css/g/gar_1fxaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="uhxia1b7z"/><path class="gar_1fxaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:life-buoy" /></template>
