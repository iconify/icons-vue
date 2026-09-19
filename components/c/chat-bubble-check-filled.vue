<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvq26cl9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvq26cl9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-bubble-check-filled" /></template>
