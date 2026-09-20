<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo454jbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="jo454jbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:clothing-store" /></template>
