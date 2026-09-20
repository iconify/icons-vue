<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vesf7-b_g.css';
import '../../css/h/h_auobb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vesf7-b_g"/><path class="h_auobb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:internet-network-download" /></template>
