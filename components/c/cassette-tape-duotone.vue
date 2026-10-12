<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q050sk4js.css';
import '../../css/o/oftlfvbfd.css';
import '../../css/q/qyrihfbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q050sk4js"/><path class="oftlfvbfd"/><path clip-rule="evenodd" class="qyrihfbrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cassette-tape-duotone" /></template>
