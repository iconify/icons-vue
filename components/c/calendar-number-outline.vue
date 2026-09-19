<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvtzd3b0t.css';
import '../../css/l/llds493te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="zvtzd3b0t"/><path class="llds493te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:calendar-number-outline" /></template>
