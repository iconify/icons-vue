<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thdmt63vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thdmt63vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:aspect-ratio" /></template>
