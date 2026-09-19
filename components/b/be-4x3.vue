<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9qcacyl.css';
import '../../css/b/b3pr9bc_z.css';
import '../../css/i/ihocy9b2c.css';
import '../../css/l/lkt5jbcct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="b3pr9bc_z"/><path class="ihocy9b2c"/><path class="lkt5jbcct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:be-4x3" /></template>
