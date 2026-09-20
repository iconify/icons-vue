<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbvpz2owh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cbvpz2owh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:anchor-medal" /></template>
