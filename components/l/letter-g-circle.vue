<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_30q3cbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_30q3cbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-g-circle" /></template>
