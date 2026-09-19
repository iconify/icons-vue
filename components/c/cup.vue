<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/y/yw5nrdgml.css';
import '../../css/l/lxdln76cc.css';
import '../../css/j/jnskwr84b.css';
import '../../css/r/rfia81eko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":49,"height":48};
const content = `<g class="hit3bi0-v"><path class="yw5nrdgml"/><path class="lxdln76cc"/><path class="jnskwr84b"/><path class="rfia81eko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:cup" /></template>
