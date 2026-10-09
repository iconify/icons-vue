<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un1r_mbsq.css';
import '../../css/x/xffa8bcjg.css';
import '../../css/p/pu1_4vbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="un1r_mbsq"/><path class="xffa8bcjg"/><path class="pu1_4vbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biodiversity-48-bold" /></template>
