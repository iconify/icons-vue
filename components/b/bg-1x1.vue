<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onyqr8g1f.css';
import '../../css/a/a5ljf0bmb.css';
import '../../css/h/hcj7zv6_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="onyqr8g1f"/><path class="a5ljf0bmb"/><path class="hcj7zv6_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:bg-1x1" /></template>
