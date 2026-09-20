<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/l2cvx7bcp.css';
import '../../css/u/ug7ux5rvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect transform="rotate(-45 2 8.364)" class="l2cvx7bcp"/><path class="ug7ux5rvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:band-aids-line" /></template>
