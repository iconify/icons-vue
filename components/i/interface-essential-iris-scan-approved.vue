<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck7z_9alj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ck7z_9alj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-iris-scan-approved" /></template>
