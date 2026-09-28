<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jb730ab3d.css';
import '../../css/g/g9av7kz0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="jb730ab3d"/><path vector-effect="non-scaling-stroke" class="g9av7kz0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:heading-level-4" /></template>
