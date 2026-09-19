<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq_0qxfmx.css';
import '../../css/y/yu51uzbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zq_0qxfmx"/><path class="yu51uzbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:broken-link" /></template>
