<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agsf1c4-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agsf1c4-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eraser-fill" /></template>
