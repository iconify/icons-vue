<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0mujzp-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0mujzp-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dock-window" /></template>
