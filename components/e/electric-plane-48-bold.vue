<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djc8x4bhg.css';
import '../../css/l/l_ts_2t7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="djc8x4bhg"/><path class="l_ts_2t7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-plane-48-bold" /></template>
