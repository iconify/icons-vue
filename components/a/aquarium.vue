<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxa23ha5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="uxa23ha5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:aquarium" /></template>
