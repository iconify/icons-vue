<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmo9ppb1i.css';
import '../../css/r/rf6qy1bai.css';
import '../../css/h/hsg9le06j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="lmo9ppb1i"><path class="rf6qy1bai"/><path class="hsg9le06j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate-color:diagram-split-horizontal" /></template>
