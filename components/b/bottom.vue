<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy692n8eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wy692n8eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:bottom" /></template>
