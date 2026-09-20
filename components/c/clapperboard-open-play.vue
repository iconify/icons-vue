<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd1zls1cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd1zls1cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clapperboard-open-play" /></template>
