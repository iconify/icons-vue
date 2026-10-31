<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lezojdu3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lezojdu3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-conversation-circle-round" /></template>
