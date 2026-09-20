<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5jhss4ab.css';
import '../../css/l/lypy48boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z5jhss4ab"/><path class="lypy48boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:logo-social-media-tiktok" /></template>
