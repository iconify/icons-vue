<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq2f81b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq2f81b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-heart-line" /></template>
