<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v9g0gvvce.css';
import '../../css/j/j6g30jbys.css';
import '../../css/q/q24x7obey.css';
import '../../css/s/s3or9_bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="v9g0gvvce"/><path clip-rule="evenodd" class="j6g30jbys"/><path clip-rule="evenodd" class="q24x7obey"/><path class="s3or9_bry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:bell-remove" /></template>
