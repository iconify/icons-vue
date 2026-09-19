<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdygiiwqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdygiiwqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:chat-bubble-bottom-center-text" /></template>
