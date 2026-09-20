<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm-k4xbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm-k4xbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:m5stack" /></template>
