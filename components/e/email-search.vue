<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/c_4c5cc2r.css';
import '../../css/q/qj-74wbfr.css';
import '../../css/o/outxdn7yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="c_4c5cc2r"/><circle class="qj-74wbfr"/><path class="outxdn7yt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:email-search" /></template>
