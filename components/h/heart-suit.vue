<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc41vib9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hc41vib9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:heart-suit" /></template>
