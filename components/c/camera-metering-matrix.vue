<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5f9-ubrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5f9-ubrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-metering-matrix" /></template>
