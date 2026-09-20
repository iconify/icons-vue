<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a28b4nb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="a28b4nb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mail-chat-bubble-square-messages-message-bubble-chat-square" /></template>
