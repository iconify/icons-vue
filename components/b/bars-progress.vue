<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xru7odbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xru7odbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bars-progress" /></template>
