<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/eme4c3hbl.css';
import '../../css/g/grjaxzi4b.css';
import '../../css/n/nk07rpvti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect class="eme4c3hbl"/><path class="grjaxzi4b"/><path class="nk07rpvti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:door-handle" /></template>
