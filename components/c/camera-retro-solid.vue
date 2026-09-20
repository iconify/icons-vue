<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxphk2e7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yxphk2e7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:camera-retro-solid" /></template>
