<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq76f0bli.css';
import '../../css/k/kjglpe2ae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rq76f0bli"/><path class="kjglpe2ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:connectwise-brightgauge-dark" /></template>
