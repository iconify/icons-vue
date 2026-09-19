<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/z/z6s5imbxf.css';
import '../../css/u/ue1cjpbqo.css';
import '../../css/u/uqkw_fe5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="z6s5imbxf"/><path class="ue1cjpbqo"/><path class="uqkw_fe5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:edit-name" /></template>
