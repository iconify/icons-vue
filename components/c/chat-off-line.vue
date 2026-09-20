<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzkzmbc4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzkzmbc4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-off-line" /></template>
