<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh3yrdbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xh3yrdbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:button-stop-flat" /></template>
