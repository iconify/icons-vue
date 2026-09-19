<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/bxwdkp16c.css';
import '../../css/w/w-5ltnd5j.css';
import '../../css/l/l_t1d5bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="bxwdkp16c"/><path class="w-5ltnd5j"/><path class="l_t1d5bcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:eyes" /></template>
