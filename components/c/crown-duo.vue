<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rltf4qbkr.css';
import '../../css/u/ui32hib9b.css';
import '../../css/b/b-jt0k5cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="rltf4qbkr"/><path class="ui32hib9b wm-a"/><path class="b-jt0k5cr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:crown-duo" /></template>
