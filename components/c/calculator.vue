<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/c/chlufk9hn.css';
import '../../css/z/zqxiydbcq.css';
import '../../css/u/u3mutbcwy.css';
import '../../css/e/etehlz6wq.css';
import '../../css/f/fds2zou2y.css';
import '../../css/q/qd1so1ilw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="chlufk9hn"/><path class="zqxiydbcq"/><path class="u3mutbcwy"/><path class="etehlz6wq"/><path class="fds2zou2y"/><path class="qd1so1ilw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:calculator" /></template>
