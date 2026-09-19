<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smvx7zb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="chatbubble-outline"><path class="(Stroke) 27 Ellipse smvx7zb7y" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:chatbubble-outline" /></template>
