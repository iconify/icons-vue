<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbt1e7ztl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wbt1e7ztl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bookmark-simple-slash" /></template>
