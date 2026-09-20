<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wotr_1b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wotr_1b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:axis-y-rotate-counterclockwise" /></template>
