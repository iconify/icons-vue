<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/o/ozbdiq3aa.css';
import '../../css/g/g-zi73ava.css';
import '../../css/g/g698gzb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><rect class="ozbdiq3aa"/><path class="g-zi73ava"/><path class="g698gzb4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:iphone" /></template>
