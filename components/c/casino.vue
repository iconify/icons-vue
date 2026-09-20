<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe8xt8c8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="fe8xt8c8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:casino" /></template>
