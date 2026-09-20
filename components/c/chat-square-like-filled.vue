<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu6dr2k5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zu6dr2k5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-square-like-filled" /></template>
