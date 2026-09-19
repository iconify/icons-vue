<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/kuqdplbdl.css';
import '../../css/t/tqb_6nb6c.css';
import '../../css/v/vim-wxqdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="kuqdplbdl"/><circle class="tqb_6nb6c"/><path class="vim-wxqdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:endpoint-square" /></template>
