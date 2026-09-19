<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hqvb99byo.css';
import '../../css/c/c73e0yd1g.css';
import '../../css/r/rp2ocszvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hqvb99byo"/><path class="c73e0yd1g"/><path class="rp2ocszvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:id-card-lanyard" /></template>
