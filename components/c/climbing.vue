<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy4y49t-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="uy4y49t-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:climbing" /></template>
