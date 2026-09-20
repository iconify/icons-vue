<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5ari2byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="e5ari2byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:gas-station" /></template>
