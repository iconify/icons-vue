<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6q97dpha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6q97dpha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chat-messages" /></template>
