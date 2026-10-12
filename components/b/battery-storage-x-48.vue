<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3j0gtb9o.css';
import '../../css/l/l7s7xcc2s.css';
import '../../css/l/lfph_mk7l.css';
import '../../css/r/r6tthcc7g.css';
import '../../css/b/bdkl8-dne.css';
import '../../css/j/j3cy-fbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u3j0gtb9o"/><path class="l7s7xcc2s"/><path class="lfph_mk7l"/><path class="r6tthcc7g"/><path class="bdkl8-dne"/><path class="j3cy-fbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-storage-x-48" /></template>
