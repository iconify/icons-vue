<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq1me686k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="dq1me686k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:laundry" /></template>
