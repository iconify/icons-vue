<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hladx8kwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hladx8kwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-check-bold" /></template>
