<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/f/f5po9bcuy.css';
import '../../css/m/mndv0_ajw.css';
import '../../css/c/cwzlrubce.css';
import '../../css/b/bpjd_mbew.css';
import '../../css/q/q25pvze9b.css';
import '../../css/p/p9hceabxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="f5po9bcuy"/><path class="mndv0_ajw"/><rect class="cwzlrubce"/><path class="bpjd_mbew"/><path class="q25pvze9b"/><path class="p9hceabxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:file-pdf-one" /></template>
