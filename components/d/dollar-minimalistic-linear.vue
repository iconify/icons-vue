<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/g/gwtb9fb5e.css';
import '../../css/p/p3a3-wxlk.css';
import '../../css/p/p9ekrnbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><path class="gwtb9fb5e"/><path class="p3a3-wxlk"/><path class="p9ekrnbem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dollar-minimalistic-linear" /></template>
