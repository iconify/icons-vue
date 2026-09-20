<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkm0tz84w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkm0tz84w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invert-colors-off" /></template>
