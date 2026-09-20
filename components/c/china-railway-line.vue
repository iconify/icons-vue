<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikale_bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikale_bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:china-railway-line" /></template>
