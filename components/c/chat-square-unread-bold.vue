<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0boe6iuj.css';
import '../../css/w/wstn7hb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0boe6iuj"/><path class="wstn7hb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-unread-bold" /></template>
