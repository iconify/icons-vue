<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uh7ju2rpw.css';
import '../../css/l/l6-0iw9fz.css';
import '../../css/h/haaieybaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uh7ju2rpw"/><path class="l6-0iw9fz"/><path class="haaieybaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:card-add" /></template>
