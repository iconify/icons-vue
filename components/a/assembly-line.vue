<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/o/o_-ocsn5i.css';
import '../../css/t/tlktmtbnx.css';
import '../../css/v/vm5l4wnay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="o_-ocsn5i"/><path class="tlktmtbnx"/><circle class="vm5l4wnay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:assembly-line" /></template>
