<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq_gk5baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="pq_gk5baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:bakery" /></template>
