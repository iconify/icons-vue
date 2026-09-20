<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si3wqrb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="si3wqrb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:gym" /></template>
