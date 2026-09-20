<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx3-p01if.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx3-p01if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:corner-down-right-line" /></template>
