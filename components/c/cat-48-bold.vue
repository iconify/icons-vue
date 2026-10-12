<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk_lpbr1e.css';
import '../../css/c/cmf_awb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lk_lpbr1e"/><path class="cmf_awb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cat-48-bold" /></template>
