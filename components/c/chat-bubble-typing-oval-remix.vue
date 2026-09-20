<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aljvuwvzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aljvuwvzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:chat-bubble-typing-oval-remix" /></template>
