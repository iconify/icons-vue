<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb2wu4hat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb2wu4hat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:heart-pulse-fill" /></template>
