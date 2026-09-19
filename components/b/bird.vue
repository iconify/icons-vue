<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rg0y1cyif.css';
import '../../css/l/lwxrhtbij.css';
import '../../css/m/m4encacuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="rg0y1cyif"/><path class="lwxrhtbij"/><path class="m4encacuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:bird" /></template>
