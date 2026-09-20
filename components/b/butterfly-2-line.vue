<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu8jyibot.css';
import '../../css/f/fa7sd-bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu8jyibot"/><path class="fa7sd-bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:butterfly-2-line" /></template>
