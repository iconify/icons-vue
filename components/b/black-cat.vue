<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/h/hxpb80bjk.css';
import '../../css/x/xjj57vife.css';
import '../../css/f/fhns2vbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="hxpb80bjk"/><path class="xjj57vife"/><path class="fhns2vbpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:black-cat" /></template>
