<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a-ewlxb5r.css';
import '../../css/s/sv8__t8-c.css';
import '../../css/d/dz3e1ibvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a-ewlxb5r"/><path class="sv8__t8-c wm-a"/><path class="dz3e1ibvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lightbulb-duo" /></template>
