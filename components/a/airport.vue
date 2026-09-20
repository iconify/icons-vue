<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sci_v2bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="sci_v2bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:airport" /></template>
