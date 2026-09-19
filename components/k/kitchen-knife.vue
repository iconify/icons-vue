<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t0-cvjbua.css';
import '../../css/w/w-3x32u8q.css';
import '../../css/p/pr_1mzb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="t0-cvjbua"/><path class="w-3x32u8q"/><circle class="pr_1mzb5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:kitchen-knife" /></template>
