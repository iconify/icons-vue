<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qisnddmbb.css';
import '../../css/i/i5r18_m4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qisnddmbb"/><path class="i5r18_m4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hard-hat-48" /></template>
