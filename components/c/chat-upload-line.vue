<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riqks3bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="riqks3bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-upload-line" /></template>
