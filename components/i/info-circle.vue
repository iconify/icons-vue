<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq1z-kbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cq1z-kbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:info-circle" /></template>
