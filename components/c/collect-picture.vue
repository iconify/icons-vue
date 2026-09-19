<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rr5bzobwc.css';
import '../../css/q/q6u6gfbgw.css';
import '../../css/i/io84_hbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="rr5bzobwc"/><path class="q6u6gfbgw"/><path class="io84_hbus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:collect-picture" /></template>
