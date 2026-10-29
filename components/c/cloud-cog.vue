<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/v/v40qmob5j.css';
import '../../css/g/gv3f9df9z.css';
import '../../css/m/m4sbppbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="v40qmob5j wm-k"/><path class="gv3f9df9z wm-s"/><path class="m4sbppbnj wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:cloud-cog" /></template>
