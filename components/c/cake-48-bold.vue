<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inuv3l36d.css';
import '../../css/z/zabxrlbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="inuv3l36d"/><path class="zabxrlbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cake-48-bold" /></template>
