<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/drttxikxo.css';
import '../../css/c/cr3ta5bbg.css';
import '../../css/p/p9-zrkb4g.css';
import '../../css/g/guewfbcxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="drttxikxo"/><path class="cr3ta5bbg"/><path class="p9-zrkb4g"/><path class="guewfbcxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:ios-settings" /></template>
