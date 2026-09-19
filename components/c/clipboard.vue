<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/l-xq-1bpb.css';
import '../../css/e/e4n8cdcst.css';
import '../../css/k/k-vg18sac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="l-xq-1bpb"/><path class="e4n8cdcst"/><path class="k-vg18sac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:clipboard" /></template>
