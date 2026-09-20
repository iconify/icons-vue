<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idwguvbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":631,"height":344};
const content = `<path class="idwguvbwi layer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:eli-lilly" /></template>
