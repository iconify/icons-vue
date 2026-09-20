<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkt4a4bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fkt4a4bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:chat-bubble-crack-square-solid" /></template>
