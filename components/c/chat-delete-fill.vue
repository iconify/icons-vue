<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvpz8ohbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvpz8ohbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-delete-fill" /></template>
