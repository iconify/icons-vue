<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/y/yy7m5dbrn.css';
import '../../css/e/e47sjs74x.css';
import '../../css/g/g72mfb4-p.css';
import '../../css/m/m7atqbckd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow yy7m5dbrn"/><path class="e47sjs74x wm-shadow"/><path class="g72mfb4-p"/><path class="m7atqbckd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:close" /></template>
