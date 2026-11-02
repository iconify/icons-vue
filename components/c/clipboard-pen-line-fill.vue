<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxl-6tboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxl-6tboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-pen-line-fill" /></template>
