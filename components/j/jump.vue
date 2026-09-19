<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/l/lwgt0b34p.css';
import '../../css/p/p3gg84b6g.css';
import '../../css/b/b62w8-blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="lwgt0b34p"/><path class="p3gg84b6g"/><circle class="b62w8-blj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:jump" /></template>
