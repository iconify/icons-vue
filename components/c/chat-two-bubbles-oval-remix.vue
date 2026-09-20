<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mharr2-6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mharr2-6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:chat-two-bubbles-oval-remix" /></template>
