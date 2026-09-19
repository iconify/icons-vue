<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6m34_-qc.css';
import '../../css/i/ifltctg4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y6m34_-qc"/><path class="ifltctg4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:electro-devices" /></template>
