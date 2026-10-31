<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h06u_xbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h06u_xbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-bulk-round" /></template>
