<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rowf91b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rowf91b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:badge-captions" /></template>
