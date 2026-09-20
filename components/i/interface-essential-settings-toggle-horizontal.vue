<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyf5y1bmq.css';
import '../../css/c/c74pkebbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qyf5y1bmq"/><path class="c74pkebbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-settings-toggle-horizontal" /></template>
