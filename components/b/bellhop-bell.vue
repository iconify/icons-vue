<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf_p6lzmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vf_p6lzmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bellhop-bell" /></template>
