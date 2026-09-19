<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/uaf3_62mx.css';
import '../../css/a/av9l1ko1u.css';
import '../../css/b/basw9ubgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="uaf3_62mx"/><path class="av9l1ko1u"/><path class="basw9ubgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:iwatch" /></template>
