<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t19sx_49z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t19sx_49z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:chat-question-thin" /></template>
