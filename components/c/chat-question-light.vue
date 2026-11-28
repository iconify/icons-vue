<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1tq014el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u1tq014el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:chat-question-light" /></template>
