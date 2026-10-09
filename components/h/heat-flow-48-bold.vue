<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymn_1dbbh.css';
import '../../css/n/ndusirsyt.css';
import '../../css/r/r_v2nxmlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ymn_1dbbh"/><path class="ndusirsyt"/><path class="r_v2nxmlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-flow-48-bold" /></template>
