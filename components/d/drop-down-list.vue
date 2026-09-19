<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/d/d8561dbcl.css';
import '../../css/s/sur6g4xqv.css';
import '../../css/r/rw4ic0bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="d8561dbcl"/><path class="sur6g4xqv"/><path class="rw4ic0bsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:drop-down-list" /></template>
