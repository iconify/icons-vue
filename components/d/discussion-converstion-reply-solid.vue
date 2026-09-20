<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc4xw-vcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jc4xw-vcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:discussion-converstion-reply-solid" /></template>
