<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p08234b8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p08234b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:barrel-2-fill" /></template>
