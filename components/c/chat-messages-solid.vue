<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz2j1vbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz2j1vbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chat-messages-solid" /></template>
