<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fab1iab3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fab1iab3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:infrared-thermometer-fill" /></template>
