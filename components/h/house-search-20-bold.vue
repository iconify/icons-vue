<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmgp-hp4m.css';
import '../../css/r/rdst0hbya.css';
import '../../css/y/yulc80b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rmgp-hp4m"/><path class="rdst0hbya"/><path class="yulc80b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-search-20-bold" /></template>
