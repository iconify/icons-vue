<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/e824nmyse.css';
import '../../css/t/tp6mttbwd.css';
import '../../css/m/mapw8zb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="e824nmyse"/><path class="tp6mttbwd"/><path class="mapw8zb5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:card-reader" /></template>
