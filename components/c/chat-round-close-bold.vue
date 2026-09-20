<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se67ui62b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="se67ui62b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-close-bold" /></template>
