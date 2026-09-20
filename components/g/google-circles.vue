<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3m2yvuye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3m2yvuye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-circles" /></template>
