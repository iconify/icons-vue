<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-tjpjsqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="e-tjpjsqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:health" /></template>
