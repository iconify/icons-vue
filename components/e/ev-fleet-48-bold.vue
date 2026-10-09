<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liisccame.css';
import '../../css/h/h6e7wy_ms.css';
import '../../css/a/a24rft0do.css';
import '../../css/n/nnwy57bcc.css';
import '../../css/y/yqhmzccbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="liisccame"/><path class="h6e7wy_ms"/><path class="a24rft0do"/><path class="nnwy57bcc"/><path class="yqhmzccbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-fleet-48-bold" /></template>
