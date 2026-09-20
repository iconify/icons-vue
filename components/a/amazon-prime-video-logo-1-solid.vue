<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykt_9484h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ykt_9484h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:amazon-prime-video-logo-1-solid" /></template>
