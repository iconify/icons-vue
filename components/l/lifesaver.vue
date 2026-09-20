<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/n4yelbbex.css';
import '../../css/a/azn53ws-b.css';
import '../../css/p/ph3p_zb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="n4yelbbex"/><path vector-effect="non-scaling-stroke" class="azn53ws-b"/><path vector-effect="non-scaling-stroke" class="ph3p_zb4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:lifesaver" /></template>
