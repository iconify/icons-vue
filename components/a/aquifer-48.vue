<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgupoibyg.css';
import '../../css/u/uc3zgsbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rgupoibyg"/><path class="uc3zgsbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:aquifer-48" /></template>
