<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opmr5m07o.css';
import '../../css/g/gxsk1y4aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opmr5m07o"/><path class="gxsk1y4aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-down-right-stroke-square" /></template>
