<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/p/puu5ycbjz.css';
import '../../css/d/dujv7kbvf.css';
import '../../css/e/eytnxnxck.css';
import '../../css/c/contxzbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="puu5ycbjz"/><path class="dujv7kbvf"/><path class="eytnxnxck"/><path class="contxzbor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cooking" /></template>
