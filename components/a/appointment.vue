<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/c/c8rreybsc.css';
import '../../css/a/ajen750kr.css';
import '../../css/h/hek85dbhv.css';
import '../../css/t/tjuoppb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><circle class="c8rreybsc"/><path class="ajen750kr"/><circle class="hek85dbhv"/><path class="tjuoppb1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:appointment" /></template>
