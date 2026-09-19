<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2hu5m5ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="r2hu5m5ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:code-fork" /></template>
