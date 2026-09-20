<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/raf3v2b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="raf3v2b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:filter" /></template>
