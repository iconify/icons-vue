<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmj2aibcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmj2aibcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-penguin" /></template>
