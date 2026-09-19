<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkxxtlbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":512};
const content = `<path clip-rule="evenodd" class="qkxxtlbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lex" /></template>
