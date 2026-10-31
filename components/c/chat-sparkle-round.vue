<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzn4wdozi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzn4wdozi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-sparkle-round" /></template>
