<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/dau6xu-gm.css';
import '../../css/i/ih0df-bqd.css';
import '../../css/i/i4uqfac5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dau6xu-gm"/><rect class="ih0df-bqd"/><path class="i4uqfac5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:calibrated-meter" /></template>
