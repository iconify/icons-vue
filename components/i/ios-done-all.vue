<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf8i4wb_q.css';
import '../../css/h/hn3vxocrc.css';
import '../../css/m/mhn7bwbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mf8i4wb_q"/><path class="hn3vxocrc"/><path class="mhn7bwbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-done-all" /></template>
