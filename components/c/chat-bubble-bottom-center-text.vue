<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-kp13e4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-kp13e4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-bottom-center-text" /></template>
