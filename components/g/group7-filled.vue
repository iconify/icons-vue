<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/m3d9b5bic.css';
import '../../css/t/tb5ln68hg.css';
import '../../css/v/vx2joeb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m3d9b5bic"/><path class="tb5ln68hg"/><path class="vx2joeb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:group7-filled" /></template>
