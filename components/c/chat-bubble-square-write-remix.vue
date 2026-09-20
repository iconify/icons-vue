<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgoz6bvzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgoz6bvzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:chat-bubble-square-write-remix" /></template>
