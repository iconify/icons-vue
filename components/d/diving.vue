<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trz6_5eei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="trz6_5eei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:diving" /></template>
