<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkvt3bczz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="figma-logo-outline"><path class="(Stroke) Vector wkvt3bczz" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:figma-logo-outline" /></template>
