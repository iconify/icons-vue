<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flrhu3bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="flrhu3bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:camera-video-remix" /></template>
