<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/s/snx9u9blb.css';
import '../../css/h/hv9wxdvso.css';
import '../../css/i/ib_y_5qcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="snx9u9blb"/><path class="hv9wxdvso"/><path class="ib_y_5qcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:box-light" /></template>
