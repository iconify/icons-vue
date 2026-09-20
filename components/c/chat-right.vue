<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjzfa1bwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gjzfa1bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:chat-right" /></template>
