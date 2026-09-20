<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls58l8zhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ls58l8zhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:canoe-under-wrench" /></template>
