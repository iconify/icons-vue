<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxhj9lv9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zxhj9lv9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-line2x-outline" /></template>
