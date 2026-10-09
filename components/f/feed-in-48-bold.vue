<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl_of99ub.css';
import '../../css/v/vucxpmn0x.css';
import '../../css/e/e2qoovbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tl_of99ub"/><path class="vucxpmn0x"/><path class="e2qoovbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:feed-in-48-bold" /></template>
