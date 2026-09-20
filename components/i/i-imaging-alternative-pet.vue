<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg4w013as.css';
import '../../css/z/z0xcrnbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":65,"height":64};
const content = `<path class="yg4w013as"/><path class="z0xcrnbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-imaging-alternative-pet" /></template>
