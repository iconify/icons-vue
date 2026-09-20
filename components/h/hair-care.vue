<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2f6fwbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="n2f6fwbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:hair-care" /></template>
