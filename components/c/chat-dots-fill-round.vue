<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g83pymb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g83pymb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-dots-fill-round" /></template>
