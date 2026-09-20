<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3tc17cay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i3tc17cay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chat-bubble-square-warning-solid" /></template>
