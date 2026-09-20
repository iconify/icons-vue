<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivqjku9uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ivqjku9uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:boat-tour" /></template>
