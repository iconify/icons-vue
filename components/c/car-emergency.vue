<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzi-d4bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzi-d4bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-emergency" /></template>
