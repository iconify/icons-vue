<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgdfcyd0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgdfcyd0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards-playing-spade-outline" /></template>
