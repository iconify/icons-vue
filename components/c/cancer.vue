<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/jpu0cubwf.css';
import '../../css/p/pgcwh7bgt.css';
import '../../css/w/wjpvdcbgb.css';
import '../../css/e/errurjr8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="jpu0cubwf"/><path class="pgcwh7bgt"/><circle transform="rotate(-180 11 31)" class="wjpvdcbgb"/><path class="errurjr8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:cancer" /></template>
