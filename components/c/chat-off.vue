<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-sq9tbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s-sq9tbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chat-off" /></template>
