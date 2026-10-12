<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qox-itb7z.css';
import '../../css/y/yh9fei7of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qox-itb7z"/><path class="yh9fei7of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:binder-20-bold" /></template>
