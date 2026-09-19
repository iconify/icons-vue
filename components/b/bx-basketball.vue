<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy5afrstx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy5afrstx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-basketball" /></template>
