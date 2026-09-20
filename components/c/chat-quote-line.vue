<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc6ezcbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc6ezcbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-quote-line" /></template>
