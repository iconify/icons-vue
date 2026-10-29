<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/t/t5zj4129q.css';
import '../../css/b/bxjv56brc.css';
import '../../css/q/qnftlbnpd.css';
import '../../css/c/cw36_6mco.css';
import '../../css/j/jwyvidb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="t5zj4129q wm-deco"/><path class="bxjv56brc wm-deco"/><path class="qnftlbnpd wm-k"/><path class="cw36_6mco wm-a"/><path class="jwyvidb5f wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-area-blueprint" /></template>
