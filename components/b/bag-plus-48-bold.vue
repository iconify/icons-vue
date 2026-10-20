<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqivvfbyi.css';
import '../../css/m/m6q9glbvh.css';
import '../../css/k/k598mbbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aqivvfbyi"/><path class="m6q9glbvh"/><path class="k598mbbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bag-plus-48-bold" /></template>
