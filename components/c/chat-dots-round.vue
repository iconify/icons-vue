<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h09mocyzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h09mocyzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-dots-round" /></template>
