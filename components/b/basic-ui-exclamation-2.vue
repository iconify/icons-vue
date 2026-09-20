<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh064mfkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zh064mfkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-exclamation-2" /></template>
