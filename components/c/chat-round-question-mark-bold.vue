<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcsb5qxsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fcsb5qxsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-question-mark-bold" /></template>
