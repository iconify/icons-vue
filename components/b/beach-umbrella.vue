<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/j/jycvn840o.css';
import '../../css/y/y3xg51wix.css';
import '../../css/p/pqa1ftavv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="jycvn840o"/><path class="y3xg51wix"/><path class="pqa1ftavv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:beach-umbrella" /></template>
