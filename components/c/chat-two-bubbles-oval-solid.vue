<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn8x0ybtd.css';
import '../../css/s/sxeq1hglr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mn8x0ybtd"/><path class="sxeq1hglr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:chat-two-bubbles-oval-solid" /></template>
