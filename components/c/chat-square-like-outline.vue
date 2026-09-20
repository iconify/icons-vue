<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddldl_4lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddldl_4lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-like-outline" /></template>
