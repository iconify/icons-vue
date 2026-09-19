<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2fnrlbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x2fnrlbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:chat-bubble-question-solid" /></template>
