<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl8z51bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl8z51bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-text-round" /></template>
