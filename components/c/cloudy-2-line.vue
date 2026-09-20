<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1z97bb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1z97bb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cloudy-2-line" /></template>
