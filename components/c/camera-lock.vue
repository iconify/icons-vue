<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilvl92uyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilvl92uyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-lock" /></template>
