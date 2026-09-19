<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/cd0y8fbhg.css';
import '../../css/h/hpifqdbin.css';
import '../../css/t/t9unskp3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="cd0y8fbhg"/><circle class="hpifqdbin"/><circle class="t9unskp3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:list-fail" /></template>
