<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vot-hdb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="vot-hdb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:fire-station" /></template>
