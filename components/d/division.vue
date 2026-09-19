<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/knq66i4mf.css';
import '../../css/o/owghvwb3e.css';
import '../../css/j/jxsnms7hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="knq66i4mf"/><circle class="owghvwb3e"/><path class="jxsnms7hz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:division" /></template>
