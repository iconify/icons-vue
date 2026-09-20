<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tet16qbak.css';
import '../../css/w/w_q_buz-q.css';
import '../../css/z/zar5c9-1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tet16qbak"/><path class="w_q_buz-q"/><path class="zar5c9-1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-drugs-pill" /></template>
