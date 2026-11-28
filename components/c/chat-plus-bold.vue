<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhtfkdvai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mhtfkdvai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:chat-plus-bold" /></template>
