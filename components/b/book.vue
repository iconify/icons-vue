<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvzdmtb_q.css';
import '../../css/q/q1gzscbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wvzdmtb_q"/><path class="q1gzscbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:book" /></template>
