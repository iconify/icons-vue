<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbshjibkz.css';
import '../../css/g/gnx__cb0f.css';
import '../../css/i/i6lxnjb1e.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/w/whe3sybgf.css';
import '../../css/y/yahz0ib6i.css';
import '../../css/v/vpiz7xr6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="hbshjibkz"/><path class="gnx__cb0f"/><path class="i6lxnjb1e"/><g class="jn8qy4bru"><circle class="whe3sybgf"/><circle class="yahz0ib6i"/><path class="vpiz7xr6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:gear" /></template>
