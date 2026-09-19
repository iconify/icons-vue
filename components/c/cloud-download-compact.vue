<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckxvtmlqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ckxvtmlqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:cloud-download-compact" /></template>
