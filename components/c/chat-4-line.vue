<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khi6rrb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khi6rrb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-4-line" /></template>
