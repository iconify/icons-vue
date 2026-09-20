<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfi6iybpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfi6iybpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:layout-solid" /></template>
