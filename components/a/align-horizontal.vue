<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0c8k3y3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="s0c8k3y3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:align-horizontal" /></template>
