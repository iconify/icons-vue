<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/b74gn3bkm.css';
import '../../css/e/eucewobtj.css';
import '../../css/j/jta9gpb_x.css';
import '../../css/d/dxqwydcbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="b74gn3bkm"/><path class="eucewobtj"/><path class="jta9gpb_x"/><path class="dxqwydcbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:increase-the-scale" /></template>
