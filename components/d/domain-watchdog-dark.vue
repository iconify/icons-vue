<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4yt86kns.css';
import '../../css/f/fayfq0oyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<path class="i4yt86kns"/><path class="fayfq0oyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:domain-watchdog-dark" /></template>
