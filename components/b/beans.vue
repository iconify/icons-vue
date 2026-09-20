<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3d2xsbfa.css';
import '../../css/o/o2zoxdw1l.css';
import '../../css/s/sqkqqys5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="v3d2xsbfa"/><path class="o2zoxdw1l"/><path class="sqkqqys5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:beans" /></template>
