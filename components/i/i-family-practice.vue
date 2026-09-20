<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr_rtccfq.css';
import '../../css/q/q3s24obkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xr_rtccfq"/><path class="q3s24obkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-family-practice" /></template>
