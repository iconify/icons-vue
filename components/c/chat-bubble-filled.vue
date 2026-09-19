<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf2f5y-yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf2f5y-yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-bubble-filled" /></template>
