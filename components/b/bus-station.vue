<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyp1fvbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="oyp1fvbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:bus-station" /></template>
