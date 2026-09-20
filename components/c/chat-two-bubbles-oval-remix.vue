<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hov0yh0oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hov0yh0oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chat-two-bubbles-oval-remix" /></template>
