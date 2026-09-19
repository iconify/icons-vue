<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuhqa_xqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fuhqa_xqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:letrina2x-outline" /></template>
