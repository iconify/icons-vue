<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3j0gtb9o.css';
import '../../css/l/l7s7xcc2s.css';
import '../../css/l/lfph_mk7l.css';
import '../../css/r/r6tthcc7g.css';
import '../../css/z/z4sj3ixdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u3j0gtb9o"/><path class="l7s7xcc2s"/><path class="lfph_mk7l"/><path class="r6tthcc7g"/><path class="z4sj3ixdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-storage-check-48" /></template>
