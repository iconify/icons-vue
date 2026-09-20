<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dftf9rvck.css';
import '../../css/q/qpzo5btlb.css';
import '../../css/o/o49t8rbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="dftf9rvck"/><path class="qpzo5btlb"/><path class="o49t8rbju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:atom-alt" /></template>
