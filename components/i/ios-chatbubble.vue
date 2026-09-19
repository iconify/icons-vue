<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb7zywb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cb7zywb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-chatbubble" /></template>
