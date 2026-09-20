<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a55cl3b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a55cl3b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-history-line" /></template>
