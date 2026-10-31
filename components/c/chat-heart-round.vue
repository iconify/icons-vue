<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkpkt12ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkpkt12ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-heart-round" /></template>
