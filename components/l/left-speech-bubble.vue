<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av32gzy1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="av32gzy1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:left-speech-bubble" /></template>
