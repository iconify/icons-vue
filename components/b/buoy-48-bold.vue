<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p83hrs6_m.css';
import '../../css/z/zy1--_bqv.css';
import '../../css/e/ewz0dq5ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p83hrs6_m"/><path class="zy1--_bqv"/><path class="ewz0dq5ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:buoy-48-bold" /></template>
