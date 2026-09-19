<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/c-bbc_bpd.css';
import '../../css/c/c5g7-u9cc.css';
import '../../css/l/l54so-d8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="c-bbc_bpd"/><path class="c5g7-u9cc"/><path class="l54so-d8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bank" /></template>
