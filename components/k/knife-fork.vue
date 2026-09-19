<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lf18mo9uc.css';
import '../../css/z/z03nzwvng.css';
import '../../css/o/o2qtt6bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="lf18mo9uc"/><path class="z03nzwvng"/><path class="o2qtt6bjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:knife-fork" /></template>
