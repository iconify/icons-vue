<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lja_-7uem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lja_-7uem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-call-bold" /></template>
