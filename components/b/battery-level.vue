<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/ux_jcbb_g.css';
import '../../css/p/pdhw_hbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ux_jcbb_g"/><path class="pdhw_hbkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:battery-level" /></template>
