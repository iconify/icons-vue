<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/a/a459j710d.css';
import '../../css/t/tblv8fb2h.css';
import '../../css/a/a58oazbjd.css';
import '../../css/r/riz8lqbnz.css';
import '../../css/r/rhk20g9nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><rect class="a459j710d"/><path class="tblv8fb2h"/><circle class="a58oazbjd"/><circle class="riz8lqbnz"/><path class="rhk20g9nd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:gift-bag" /></template>
