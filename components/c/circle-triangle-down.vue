<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/w/w4tslibsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="shu3xdl9q"/><path class="w4tslibsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:circle-triangle-down" /></template>
