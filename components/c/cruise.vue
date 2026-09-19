<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/e/epr703v6w.css';
import '../../css/h/h8t75bbcu.css';
import '../../css/m/mjtgadbkn.css';
import '../../css/n/nmcxl3q8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="epr703v6w"/><path class="h8t75bbcu"/><path class="mjtgadbkn"/><path class="nmcxl3q8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cruise" /></template>
