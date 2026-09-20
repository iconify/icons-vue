<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i00exacev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="i00exacev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:department-store" /></template>
