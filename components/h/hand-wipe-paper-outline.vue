<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lleu6zbks.css';
import '../../css/c/cmwq_sz7g.css';
import '../../css/n/nhl_5_bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="lleu6zbks"/><path class="cmwq_sz7g"/><path class="nhl_5_bhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hand-wipe-paper-outline" /></template>
