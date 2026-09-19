<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5xaexbmp.css';
import '../../css/r/rp66vlbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g5xaexbmp"/><path class="rp66vlbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:edge-service" /></template>
