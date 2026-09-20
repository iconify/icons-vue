<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwk2ih8jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwk2ih8jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:audio-input-stereo-minijack" /></template>
