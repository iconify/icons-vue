<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv-m53agm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hv-m53agm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:chat-bubble-typing-oval-remix" /></template>
