<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4kr7db0h.css';
import '../../css/o/oc0vi5bvd.css';
import '../../css/n/n09t0lk8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="k4kr7db0h"><path class="oc0vi5bvd"/><path class="n09t0lk8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:location-pin-off-bold" /></template>
