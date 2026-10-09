<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlsrljbwz.css';
import '../../css/v/veuurfbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rlsrljbwz"/><path class="veuurfbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:compliance-48" /></template>
