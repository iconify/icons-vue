<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf2c8xxts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf2c8xxts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-thread-fill" /></template>
