<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv4f6tbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv4f6tbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:artboard-line" /></template>
