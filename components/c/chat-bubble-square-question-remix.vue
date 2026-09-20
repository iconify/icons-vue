<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbijfxohp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wbijfxohp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chat-bubble-square-question-remix" /></template>
