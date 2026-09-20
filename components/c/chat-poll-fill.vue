<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj0k13b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj0k13b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-poll-fill" /></template>
