<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyyu2o1ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uyyu2o1ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eternal-vows" /></template>
