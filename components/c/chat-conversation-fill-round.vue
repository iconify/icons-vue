<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8uoaj-wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8uoaj-wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-conversation-fill-round" /></template>
