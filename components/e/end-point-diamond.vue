<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-cybfbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m-cybfbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:end-point-diamond" /></template>
