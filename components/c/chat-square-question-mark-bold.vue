<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqluux8oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lqluux8oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-question-mark-bold" /></template>
