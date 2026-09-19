<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/nb0ci_ujs.css';
import '../../css/k/kdubn7zbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="nb0ci_ujs"/><path class="kdubn7zbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:egg-one" /></template>
