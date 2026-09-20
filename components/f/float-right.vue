<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s655yl9ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s655yl9ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:float-right" /></template>
