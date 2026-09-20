<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj4lkbbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj4lkbbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chat-dots-solid" /></template>
