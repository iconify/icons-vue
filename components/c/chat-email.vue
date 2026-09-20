<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpqfbubif.css';
import '../../css/m/m4dq5vbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cpqfbubif"/><path class="m4dq5vbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:chat-email" /></template>
