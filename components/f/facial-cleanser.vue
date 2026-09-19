<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/s/shsp_xb_i.css';
import '../../css/g/ghb_84b2f.css';
import '../../css/j/jgj6o_1pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="shsp_xb_i"/><path class="ghb_84b2f"/><path class="jgj6o_1pm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:facial-cleanser" /></template>
