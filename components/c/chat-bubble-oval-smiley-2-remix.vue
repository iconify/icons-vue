<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w35k3sp7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w35k3sp7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chat-bubble-oval-smiley-2-remix" /></template>
