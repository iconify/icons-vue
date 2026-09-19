<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/x/x_5bsx01w.css';
import '../../css/c/clg9eiblv.css';
import '../../css/f/f47gc0bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="x_5bsx01w"/><circle class="clg9eiblv"/><path class="f47gc0bvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:archery" /></template>
