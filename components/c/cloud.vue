<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el98ugclt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="el98ugclt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:cloud" /></template>
