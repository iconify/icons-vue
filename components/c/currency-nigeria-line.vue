<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es5tsw1hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es5tsw1hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-nigeria-line" /></template>
