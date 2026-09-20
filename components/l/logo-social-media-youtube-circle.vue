<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9y4dyb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i9y4dyb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:logo-social-media-youtube-circle" /></template>
