<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdcz7gq1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdcz7gq1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-dots-fill-round" /></template>
