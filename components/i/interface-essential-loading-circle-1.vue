<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2p99079n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e2p99079n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-loading-circle-1" /></template>
