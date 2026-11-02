<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da6l0slvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da6l0slvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-3-ai-fill" /></template>
