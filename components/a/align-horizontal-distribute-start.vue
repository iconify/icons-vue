<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc-jrob2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc-jrob2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-horizontal-distribute-start" /></template>
