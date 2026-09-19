<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpkmfgbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpkmfgbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-video-01" /></template>
