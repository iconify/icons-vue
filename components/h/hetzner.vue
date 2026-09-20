<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx_fucb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx_fucb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hetzner" /></template>
