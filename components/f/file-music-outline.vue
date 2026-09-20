<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq5o1ytlu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq5o1ytlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-music-outline" /></template>
