<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bv9v4xlge.css';
import '../../css/j/jb730ab3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="bv9v4xlge"/><path vector-effect="non-scaling-stroke" class="jb730ab3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:heading-level-1" /></template>
