<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4mpn3iau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4mpn3iau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-lock-outline" /></template>
