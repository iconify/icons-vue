<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/d/d30aez8nr.css';
import '../../css/x/xij1iob8t.css';
import '../../css/v/vjydmy47l.css';
import '../../css/k/kunkzfb7p.css';
import '../../css/o/oe1d-srie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="d30aez8nr"/><path class="xij1iob8t"/><path class="vjydmy47l"/><rect class="kunkzfb7p"/><path class="oe1d-srie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:gift" /></template>
