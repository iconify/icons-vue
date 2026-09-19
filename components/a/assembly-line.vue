<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/bdeot9bnh.css';
import '../../css/t/tlktmtbnx.css';
import '../../css/p/plf46m9uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="bdeot9bnh"/><path class="tlktmtbnx"/><circle class="plf46m9uf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:assembly-line" /></template>
