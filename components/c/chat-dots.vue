<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0_ubqbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0_ubqbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chat-dots" /></template>
