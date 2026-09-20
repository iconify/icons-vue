<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0wtvdbfd.css';
import '../../css/r/rn0avuaev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j0wtvdbfd"/><path class="rn0avuaev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:candle-chart-solid" /></template>
