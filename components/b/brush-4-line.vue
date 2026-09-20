<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz3u-o5ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz3u-o5ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brush-4-line" /></template>
