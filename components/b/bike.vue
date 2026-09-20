<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y33_9cd0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y33_9cd0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bike" /></template>
