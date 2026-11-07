<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybu95d8og.css';
import '../../css/z/zh2x-vuty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybu95d8og"/><path clip-rule="evenodd" class="zh2x-vuty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:letter-unread-bold" /></template>
