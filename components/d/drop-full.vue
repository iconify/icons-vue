<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kez--3b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kez--3b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:drop-full" /></template>
