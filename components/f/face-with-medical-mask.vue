<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w254xvbma.css';
import '../../css/x/xdp90xgqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w254xvbma"/><path clip-rule="evenodd" class="xdp90xgqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:face-with-medical-mask" /></template>
