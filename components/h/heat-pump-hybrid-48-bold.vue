<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_epzybyz.css';
import '../../css/i/ihy07ry6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r_epzybyz"/><path class="ihy07ry6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-hybrid-48-bold" /></template>
