<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkihj-w6g.css';
import '../../css/y/yhip1xbph.css';
import '../../css/y/yau-9gbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rkihj-w6g"/><path class="yhip1xbph"/><path class="yau-9gbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:esg-20" /></template>
