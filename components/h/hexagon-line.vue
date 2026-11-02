<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s14haub6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s14haub6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hexagon-line" /></template>
