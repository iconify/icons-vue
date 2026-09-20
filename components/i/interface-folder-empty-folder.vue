<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc910e6zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xc910e6zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-folder-empty-folder" /></template>
