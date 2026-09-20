<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjacqcc1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjacqcc1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-bubble-error-filled" /></template>
