<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x57p1aczu.css';
import '../../css/g/grubd94nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="x57p1aczu"/><path class="grubd94nl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:camera" /></template>
