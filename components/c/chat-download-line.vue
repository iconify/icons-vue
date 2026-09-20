<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je8zd7f2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je8zd7f2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-download-line" /></template>
