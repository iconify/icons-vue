<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjfl23hqz.css';
import '../../css/i/i2hb8p_7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xjfl23hqz"/><path class="i2hb8p_7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:desktop-download-16" /></template>
