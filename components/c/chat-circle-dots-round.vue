<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8axp6b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8axp6b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-dots-round" /></template>
