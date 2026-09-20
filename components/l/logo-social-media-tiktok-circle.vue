<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g87b65bny.css';
import '../../css/t/t8sx1mbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g87b65bny"/><path class="t8sx1mbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:logo-social-media-tiktok-circle" /></template>
