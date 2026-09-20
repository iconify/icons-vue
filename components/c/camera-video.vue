<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fca4z16-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fca4z16-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:camera-video" /></template>
