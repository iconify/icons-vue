<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co2uwj05c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co2uwj05c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camcorder-off-fill" /></template>
