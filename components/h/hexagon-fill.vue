<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff1pz61xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff1pz61xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hexagon-fill" /></template>
