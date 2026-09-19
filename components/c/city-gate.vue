<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/blfoir3tq.css';
import '../../css/l/lm9e4db0f.css';
import '../../css/l/lazl2-mwt.css';
import '../../css/d/d-m6ebcne.css';
import '../../css/p/pw2bzpbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="blfoir3tq"/><path class="lm9e4db0f"/><path class="lazl2-mwt"/><path class="d-m6ebcne"/><path class="pw2bzpbnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:city-gate" /></template>
