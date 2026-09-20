<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu6_npblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu6_npblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-smile-ai-fill" /></template>
