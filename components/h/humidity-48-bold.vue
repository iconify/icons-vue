<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpqifubxl.css';
import '../../css/b/bscrhu_dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dpqifubxl"/><path class="bscrhu_dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:humidity-48-bold" /></template>
