<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0yh1rdxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r0yh1rdxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:help-chat-2-remix" /></template>
