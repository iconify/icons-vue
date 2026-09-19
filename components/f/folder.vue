<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/k56zh769s.css';
import '../../css/u/um227vekh.css';
import '../../css/t/tm9f74uep.css';
import '../../css/j/j2m8g8spq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="k56zh769s"/><path class="um227vekh"/><circle class="tm9f74uep"/><path class="j2m8g8spq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:folder" /></template>
