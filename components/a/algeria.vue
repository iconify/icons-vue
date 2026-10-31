<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyy4tpg8x.css';
import '../../css/g/g40ijz7bf.css';
import '../../css/g/gjrpy2b0q.css';
import '../../css/n/nd_n0v11x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="zyy4tpg8x"/><path class="g40ijz7bf"/><path class="gjrpy2b0q"/><path class="nd_n0v11x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:algeria" /></template>
