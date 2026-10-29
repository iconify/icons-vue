<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/v-bnvbjhd.css';
import '../../css/a/au-pabgjr.css';
import '../../css/n/nge5cfbll.css';
import '../../css/k/kz4hppbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="v-bnvbjhd wm-deco"/><path class="au-pabgjr wm-deco"/><path class="nge5cfbll wm-deco"/><path class="kz4hppbys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:armchair-blueprint" /></template>
