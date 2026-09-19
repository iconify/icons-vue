<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdi3h-vtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wdi3h-vtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:camera" /></template>
