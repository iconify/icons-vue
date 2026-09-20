<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhmw-kb7l.css';
import '../../css/i/i2b0w4dly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhmw-kb7l"/><path class="i2b0w4dly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ghidra-dark" /></template>
