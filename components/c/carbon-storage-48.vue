<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8mp0wbzm.css';
import '../../css/d/dwl2-5bwr.css';
import '../../css/u/unf30navr.css';
import '../../css/z/zrr3btyck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m8mp0wbzm"/><path class="dwl2-5bwr"/><path class="unf30navr"/><path class="zrr3btyck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-storage-48" /></template>
