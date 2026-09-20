<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v67rm8qcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v67rm8qcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-smile-ai-3-fill" /></template>
