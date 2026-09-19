<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv88xp9pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":456};
const content = `<path class="zv88xp9pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:camera-roll" /></template>
