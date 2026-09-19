<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6g3u8wjy.css';
import '../../css/u/ughd8vbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c6g3u8wjy"/><path class="ughd8vbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ice-cream" /></template>
