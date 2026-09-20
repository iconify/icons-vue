<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsqcoxl2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsqcoxl2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:angry" /></template>
