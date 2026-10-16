<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw3xaacjo.css';
import '../../css/w/wsji0bccm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="wsji0bccm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-gbt-20" /></template>
