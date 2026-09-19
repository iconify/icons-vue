<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/s/sh5o08aob.css';
import '../../css/k/kglso4bhq.css';
import '../../css/y/yjajdl9af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="sh5o08aob"/><path class="kglso4bhq"/><path class="yjajdl9af"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:cutting-one" /></template>
