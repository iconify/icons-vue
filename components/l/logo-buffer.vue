<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_1es1p0u.css';
import '../../css/i/iny3_db3v.css';
import '../../css/u/uvnpe-bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y_1es1p0u"/><path class="iny3_db3v"/><path class="uvnpe-bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-buffer" /></template>
