<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/k/kfepth7eb.css';
import '../../css/p/p6mtntqqp.css';
import '../../css/a/ado31tecw.css';
import '../../css/c/cza-liuqy.css';
import '../../css/f/fcau486fn.css';
import '../../css/x/x-2730s8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="kfepth7eb"/><path class="p6mtntqqp"/><path class="ado31tecw"/><path class="cza-liuqy"/><path class="fcau486fn"/><path clip-rule="evenodd" class="x-2730s8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:heavy-metal" /></template>
