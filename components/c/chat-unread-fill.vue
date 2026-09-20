<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k025gh__q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k025gh__q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-unread-fill" /></template>
