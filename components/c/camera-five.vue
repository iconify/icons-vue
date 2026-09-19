<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/l/l_5w5bxzf.css';
import '../../css/d/djgmrab9u.css';
import '../../css/w/whl-mbhit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="l_5w5bxzf"/><circle class="djgmrab9u"/><path class="whl-mbhit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:camera-five" /></template>
