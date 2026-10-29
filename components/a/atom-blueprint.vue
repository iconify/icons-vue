<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/d_xpcxb4a.css';
import '../../css/o/o_0yafjul.css';
import '../../css/v/vze4wuf6n.css';
import '../../css/e/eod03wb_e.css';
import '../../css/e/evx6rzb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="d_xpcxb4a wm-deco"/><path class="o_0yafjul wm-deco"/><path class="vze4wuf6n wm-deco"/><path class="eod03wb_e wm-k"/><path class="evx6rzb0c wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:atom-blueprint" /></template>
