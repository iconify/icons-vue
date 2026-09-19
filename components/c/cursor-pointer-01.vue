<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g0v5shbon.css';
import '../../css/b/bpuyxlb4i.css';
import '../../css/k/k2rgfbi6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g0v5shbon"/><path class="bpuyxlb4i"/><path class="k2rgfbi6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cursor-pointer-01" /></template>
