<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch2iuibqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ch2iuibqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-round-video" /></template>
