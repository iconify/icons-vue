<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2h6rhbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2h6rhbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:horizontal-rotate-clockwise" /></template>
