<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/mkd5n7taf.css';
import '../../css/y/y_e_yzf5i.css';
import '../../css/u/u4-tff-3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="mkd5n7taf"/><path class="y_e_yzf5i"/><path class="u4-tff-3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:check-in" /></template>
