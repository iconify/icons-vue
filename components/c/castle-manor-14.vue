<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt-67stkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zt-67stkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:castle-manor-14" /></template>
