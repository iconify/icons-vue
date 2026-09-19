<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wekkzsr2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wekkzsr2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-circle-list-filled" /></template>
