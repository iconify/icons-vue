<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1p3sh9lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n1p3sh9lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:ice-cream-square" /></template>
