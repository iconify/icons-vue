<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8yxhvbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8yxhvbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-bubble-smile-filled" /></template>
