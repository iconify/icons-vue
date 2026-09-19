<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/g/g3k3sybmt.css';
import '../../css/r/rqcd37tkp.css';
import '../../css/x/xec1e65iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="g3k3sybmt"/><path class="rqcd37tkp"/><path class="xec1e65iq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cola" /></template>
