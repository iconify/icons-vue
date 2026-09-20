<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yol05lbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="yol05lbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:cloud-refresh" /></template>
