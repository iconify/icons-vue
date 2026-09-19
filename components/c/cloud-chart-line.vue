<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdxbmxx-r.css';
import '../../css/u/u5p0img3y.css';
import '../../css/v/v3hoy0rjf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 tdxbmxx-r"/><path class="clr-i-outline clr-i-outline-path-2 u5p0img3y"/><path class="clr-i-outline clr-i-outline-path-3 v3hoy0rjf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:cloud-chart-line" /></template>
