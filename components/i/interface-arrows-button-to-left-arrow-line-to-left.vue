<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zndlmvb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zndlmvb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-button-to-left-arrow-line-to-left" /></template>
