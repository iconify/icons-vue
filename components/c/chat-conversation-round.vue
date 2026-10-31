<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjnsvebmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjnsvebmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-conversation-round" /></template>
