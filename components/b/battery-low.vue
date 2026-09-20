<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f21jypb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f21jypb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:battery-low" /></template>
