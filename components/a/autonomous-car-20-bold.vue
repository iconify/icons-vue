<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy1qryb3w.css';
import '../../css/f/fd6b2rb5y.css';
import '../../css/v/v3_b2wbqi.css';
import '../../css/m/mrygi9buu.css';
import '../../css/r/ruo1f1s0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uy1qryb3w"/><path class="fd6b2rb5y"/><path class="v3_b2wbqi"/><path class="mrygi9buu"/><path class="ruo1f1s0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:autonomous-car-20-bold" /></template>
