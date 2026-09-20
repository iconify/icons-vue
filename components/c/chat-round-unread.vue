<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6gkppsme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g6gkppsme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-round-unread" /></template>
