<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/txut7m5tj.css';
import '../../css/d/dr4lld79u.css';
import '../../css/w/ww5jfdbbd.css';
import '../../css/u/u4vwxpbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="txut7m5tj"/><path class="dr4lld79u"/><path clip-rule="evenodd" class="ww5jfdbbd"/><path class="u4vwxpbbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:cast-screen" /></template>
