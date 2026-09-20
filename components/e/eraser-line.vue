<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm0jmxb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm0jmxb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:eraser-line" /></template>
