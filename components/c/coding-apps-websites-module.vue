<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7b-ivwtn.css';
import '../../css/c/cn0ji2cwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f7b-ivwtn"/><path class="cn0ji2cwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:coding-apps-websites-module" /></template>
