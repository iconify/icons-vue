<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/s/s0v14hb6d.css';
import '../../css/b/b2ahrlpzy.css';
import '../../css/o/ofpxigb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="s0v14hb6d"/><path class="b2ahrlpzy"/><path class="ofpxigb9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:home" /></template>
