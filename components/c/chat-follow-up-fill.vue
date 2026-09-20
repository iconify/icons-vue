<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgun1xb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgun1xb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-follow-up-fill" /></template>
