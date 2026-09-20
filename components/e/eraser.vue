<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfsepcp4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mfsepcp4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:eraser" /></template>
