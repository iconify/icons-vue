<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxp0_ibgn.css';
import '../../css/u/uern_gkkh.css';
import '../../css/v/v1nh1rboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qxp0_ibgn"/><path class="uern_gkkh"/><path class="v1nh1rboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-right-square-20" /></template>
