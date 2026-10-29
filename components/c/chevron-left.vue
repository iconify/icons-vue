<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r2md8qh9v.css';
import '../../css/t/tna83ccep.css';
import '../../css/p/pmba489ow.css';
import '../../css/j/jj4qoyk8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r2md8qh9v wm-k"/><path class="tna83ccep wm-k"/><path class="pmba489ow wm-k"/><path class="jj4qoyk8g wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:chevron-left" /></template>
