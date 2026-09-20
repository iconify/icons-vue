<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guy05jlhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guy05jlhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-message-filled" /></template>
