<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0u1j7bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0u1j7bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-chat-solid" /></template>
