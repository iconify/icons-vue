<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgofl8jdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgofl8jdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-rotary-last-left" /></template>
