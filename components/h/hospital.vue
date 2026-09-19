<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/ney232e4g.css';
import '../../css/x/x6nc3bcpi.css';
import '../../css/f/ftbgqx9uv.css';
import '../../css/o/oq3xrnper.css';
import '../../css/x/x5uhmib4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ney232e4g"/><path class="x6nc3bcpi"/><path class="ftbgqx9uv"/><path class="oq3xrnper"/><path clip-rule="evenodd" class="x5uhmib4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:hospital" /></template>
