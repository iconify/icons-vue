<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg6p86m_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tg6p86m_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ffmpeg" /></template>
