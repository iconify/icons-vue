<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc4e6v2qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="yc4e6v2qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:cross" /></template>
