<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc9p2pbgb.css';
import '../../css/f/fox9vr5aw.css';
import '../../css/a/a6e_se6xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sc9p2pbgb"/><path class="fox9vr5aw"/><path class="a6e_se6xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:de-1x1" /></template>
