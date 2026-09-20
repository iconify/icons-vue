<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4kddsbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w4kddsbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:chat-bubble-square-write-solid" /></template>
