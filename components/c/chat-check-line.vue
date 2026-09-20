<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiee1zb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiee1zb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-check-line" /></template>
