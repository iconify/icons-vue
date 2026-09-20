<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5wzc0bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i5wzc0bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:chat-bubble-square-phone-solid" /></template>
