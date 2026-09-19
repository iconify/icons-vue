<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuo_w0z7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yuo_w0z7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:flower3" /></template>
