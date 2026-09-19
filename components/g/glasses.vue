<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/lfu9081tj.css';
import '../../css/u/ukpkwrb3v.css';
import '../../css/i/il6_1tbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="lfu9081tj"/><circle class="ukpkwrb3v"/><path class="il6_1tbws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:glasses" /></template>
