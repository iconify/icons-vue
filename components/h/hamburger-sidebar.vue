<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnfbogben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vnfbogben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:hamburger-sidebar" /></template>
