<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks04u331z.css';
import '../../css/a/a-sqa4bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ks04u331z"/><path class="a-sqa4bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:geojson-file" /></template>
