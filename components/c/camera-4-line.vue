<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d39d0omtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d39d0omtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:camera-4-line" /></template>
