<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/bw4wgduwd.css';
import '../../css/j/j189wtlhc.css';
import '../../css/f/flza1qbgb.css';
import '../../css/g/g2_t03b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="bw4wgduwd"/><circle class="j189wtlhc"/><path class="flza1qbgb"/><path class="g2_t03b5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:electric-iron" /></template>
