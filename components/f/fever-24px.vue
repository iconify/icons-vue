<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ucim6lbjm.css';
import '../../css/w/w98ih1blg.css';
import '../../css/d/dbz_4sb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ucim6lbjm"/><path class="w98ih1blg"/><path class="dbz_4sb8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:fever-24px" /></template>
