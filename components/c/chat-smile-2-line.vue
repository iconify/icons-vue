<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcz575ggm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcz575ggm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-smile-2-line" /></template>
