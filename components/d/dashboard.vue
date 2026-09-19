<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv5t7cb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":456};
const content = `<path class="yv5t7cb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:dashboard" /></template>
