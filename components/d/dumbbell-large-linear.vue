<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc8fm6r7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc8fm6r7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbell-large-linear" /></template>
