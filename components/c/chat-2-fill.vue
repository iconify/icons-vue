<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxhis1bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxhis1bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-2-fill" /></template>
