<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmu6_gbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="lmu6_gbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:hang-gliding" /></template>
