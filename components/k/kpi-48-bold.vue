<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/defz0cbcm.css';
import '../../css/n/nh7e1h-bk.css';
import '../../css/u/utldc7bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="defz0cbcm"/><path class="nh7e1h-bk"/><path class="utldc7bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kpi-48-bold" /></template>
