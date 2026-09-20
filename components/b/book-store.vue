<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rho2yp0gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="rho2yp0gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:book-store" /></template>
