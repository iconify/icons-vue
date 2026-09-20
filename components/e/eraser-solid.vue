<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtaondblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtaondblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:eraser-solid" /></template>
