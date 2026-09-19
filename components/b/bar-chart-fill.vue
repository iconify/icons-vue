<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkf-l0edq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hkf-l0edq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bar-chart-fill" /></template>
