<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti4q6eknm.css';
import '../../css/n/nnjcrobzw.css';
import '../../css/l/ln6f3q98l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ti4q6eknm"><path class="nnjcrobzw"/><path class="ln6f3q98l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:gymnastics-one" /></template>
