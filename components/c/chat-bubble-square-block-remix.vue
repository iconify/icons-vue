<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogrovg-la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ogrovg-la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chat-bubble-square-block-remix" /></template>
