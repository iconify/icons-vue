<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbh2nacgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="hbh2nacgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:car-repair" /></template>
