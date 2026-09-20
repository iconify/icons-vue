<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooc0r-b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ooc0r-b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-unread-outline" /></template>
