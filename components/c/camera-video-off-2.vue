<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x__8amb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x__8amb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:camera-video-off-2" /></template>
