<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vh43g_6pb.css';
import '../../css/x/xt4fmw64g.css';
import '../../css/x/xfru9th-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="vh43g_6pb"/><path class="xt4fmw64g"/><path class="xfru9th-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:doc-search-two" /></template>
