<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb0la0xpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb0la0xpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-3-fill" /></template>
