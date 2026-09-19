<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn2830bka.css';
import '../../css/v/vgycreacb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bn2830bka"/><path class="vgycreacb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-stat-alt" /></template>
