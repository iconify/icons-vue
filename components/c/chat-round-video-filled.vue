<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk37xwjgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wk37xwjgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-round-video-filled" /></template>
