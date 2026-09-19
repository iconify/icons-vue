<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/c4wfglb7q.css';
import '../../css/d/datb84q6e.css';
import '../../css/m/m9i7a_vaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="c4wfglb7q"/><path class="datb84q6e"/><path class="m9i7a_vaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-chart-pie" /></template>
