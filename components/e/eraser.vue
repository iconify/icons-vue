<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu9m68bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu9m68bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:eraser" /></template>
