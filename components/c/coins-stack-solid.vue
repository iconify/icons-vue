<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5f21kaay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f5f21kaay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:coins-stack-solid" /></template>
