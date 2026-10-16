<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t__qwuc_d.css';
import '../../css/l/lrulo-bxw.css';
import '../../css/u/uak1w0bkv.css';
import '../../css/o/o93ggxb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t__qwuc_d"/><path class="lrulo-bxw"/><path class="uak1w0bkv"/><path class="o93ggxb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-polar-20" /></template>
