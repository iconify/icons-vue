<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgdp55bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgdp55bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:alarm-snooze" /></template>
