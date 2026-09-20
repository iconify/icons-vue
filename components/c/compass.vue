<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l00dhac1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="l00dhac1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:compass" /></template>
