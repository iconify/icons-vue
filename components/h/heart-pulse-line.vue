<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y61hdrb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y61hdrb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:heart-pulse-line" /></template>
