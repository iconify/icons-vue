<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5y7lob8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5y7lob8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-metering-partial" /></template>
