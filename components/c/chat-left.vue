<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mszonib9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mszonib9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:chat-left" /></template>
