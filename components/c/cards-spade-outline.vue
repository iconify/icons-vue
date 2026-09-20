<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we0x77s-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we0x77s-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards-spade-outline" /></template>
