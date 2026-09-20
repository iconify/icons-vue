<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuojq4b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tuojq4b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-line-outline" /></template>
