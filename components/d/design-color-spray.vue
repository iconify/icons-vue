<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zheynwbwf.css';
import '../../css/p/pr7drww8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zheynwbwf"/><path class="pr7drww8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:design-color-spray" /></template>
