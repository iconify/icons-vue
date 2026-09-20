<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv6m5xotf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uv6m5xotf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:caret-square-right-solid" /></template>
