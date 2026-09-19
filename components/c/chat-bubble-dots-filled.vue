<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-8z7-lxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-8z7-lxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-bubble-dots-filled" /></template>
