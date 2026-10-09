<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u19njwbvz.css';
import '../../css/s/s7vp-wbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u19njwbvz"/><path class="s7vp-wbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-left-48-bold" /></template>
