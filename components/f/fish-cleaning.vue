<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdckdr6_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="hdckdr6_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:fish-cleaning" /></template>
