<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djkbxwbon.css';
import '../../css/i/imeyubcwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="djkbxwbon"/><path class="imeyubcwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-note" /></template>
