<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbd_2berd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbd_2berd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:earth" /></template>
