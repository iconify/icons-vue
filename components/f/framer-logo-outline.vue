<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqt6cf4sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="framer-logo-outline"><path class="(Stroke) Vector fqt6cf4sl" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:framer-logo-outline" /></template>
