<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt-f31bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt-f31bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:instrument-triangle" /></template>
