<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/x/xd0085bqe.css';
import '../../css/x/xq0l1dbym.css';
import '../../css/e/e5fqixblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="xd0085bqe"/><rect class="xq0l1dbym"/><path class="e5fqixblw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:computer" /></template>
