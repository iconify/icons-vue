<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpli6u5xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpli6u5xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-1-fill" /></template>
