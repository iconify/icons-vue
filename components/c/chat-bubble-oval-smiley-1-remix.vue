<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtsm27bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vtsm27bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:chat-bubble-oval-smiley-1-remix" /></template>
