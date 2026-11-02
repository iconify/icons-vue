<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iulz-f_yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iulz-f_yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-4-line" /></template>
