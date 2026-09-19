<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/c7xa9sbtx.css';
import '../../css/v/voorfjv1s.css';
import '../../css/l/l8hkuabxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="c7xa9sbtx"/><path class="voorfjv1s"/><path class="l8hkuabxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:blur" /></template>
