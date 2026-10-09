<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk8dzgglt.css';
import '../../css/e/eg02k6bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lk8dzgglt"/><path class="eg02k6bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electrolyser-48" /></template>
