<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuqpfgb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuqpfgb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-bubble-1-filled" /></template>
