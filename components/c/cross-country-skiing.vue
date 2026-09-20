<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oilb6wval.css';
import '../../css/j/jd3fx3b7u.css';
import '../../css/r/rydwybc0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="cuyn6tgcc"><ellipse class="oilb6wval"/><path class="jd3fx3b7u"/></g><path class="rydwybc0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:cross-country-skiing" /></template>
