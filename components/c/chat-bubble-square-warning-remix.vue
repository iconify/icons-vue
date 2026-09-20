<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv8psl0zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cv8psl0zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chat-bubble-square-warning-remix" /></template>
