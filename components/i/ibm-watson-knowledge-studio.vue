<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm_xs9bvb.css';
import '../../css/d/duuf9m24f.css';
import '../../css/l/l5ktdfbkk.css';
import '../../css/r/rij7cdc-q.css';
import '../../css/a/ao705smgf.css';
import '../../css/r/rt4cydqwb.css';
import '../../css/v/vwra7-btv.css';
import '../../css/y/yi5a0ntmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gm_xs9bvb"/><circle class="duuf9m24f"/><path class="l5ktdfbkk"/><circle class="rij7cdc-q"/><path class="ao705smgf"/><circle class="rt4cydqwb"/><path class="vwra7-btv"/><path class="yi5a0ntmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watson-knowledge-studio" /></template>
