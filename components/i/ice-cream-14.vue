<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve-xwpvcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ve-xwpvcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:ice-cream-14" /></template>
