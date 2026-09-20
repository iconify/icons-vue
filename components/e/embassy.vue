<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3byvac3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="e3byvac3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:embassy" /></template>
