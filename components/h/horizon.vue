<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj4zbobbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="uj4zbobbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:horizon" /></template>
