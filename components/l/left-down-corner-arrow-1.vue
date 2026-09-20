<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-e4hr07v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p-e4hr07v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:left-down-corner-arrow-1" /></template>
