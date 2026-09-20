<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i72gs7b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i72gs7b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:discussion-converstion-reply-remix" /></template>
