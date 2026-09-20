<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhp64zbzw.css';
import '../../css/c/cagr_ndqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rhp64zbzw"/><path class="cagr_ndqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bus" /></template>
