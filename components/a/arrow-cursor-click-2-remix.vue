<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcgn7ho-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rcgn7ho-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:arrow-cursor-click-2-remix" /></template>
