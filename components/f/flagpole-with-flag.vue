<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd86ys90j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sd86ys90j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flagpole-with-flag" /></template>
