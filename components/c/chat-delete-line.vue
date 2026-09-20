<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnr8hacgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnr8hacgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-delete-line" /></template>
