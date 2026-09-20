<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/injk-0v2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="injk-0v2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:chat-bubble-dots" /></template>
