<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vea99ibyc.css';
import '../../css/y/ybtvnxb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vea99ibyc"/><path class="ybtvnxb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-nacs-20-bold" /></template>
