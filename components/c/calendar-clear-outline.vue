<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvtzd3b0t.css';
import '../../css/m/mprowr57e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="zvtzd3b0t"/><path class="mprowr57e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:calendar-clear-outline" /></template>
