<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxex4oboi.css';
import '../../css/i/i-lfmccxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mxex4oboi"/><path class="i-lfmccxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chat-locked-16" /></template>
