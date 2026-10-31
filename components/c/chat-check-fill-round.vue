<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_a8zsbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_a8zsbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-check-fill-round" /></template>
