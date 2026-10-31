<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfhtgfw3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfhtgfw3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cpu-sparkle-round" /></template>
