<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/x/xcgj7jbrn.css';
import '../../css/n/n50kjvxhj.css';
import '../../css/y/y2ebboaxr.css';
import '../../css/k/kt5shjbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="xcgj7jbrn"/><rect class="n50kjvxhj"/><path class="y2ebboaxr"/><path class="kt5shjbak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:juice" /></template>
