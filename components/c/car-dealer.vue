<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh8h2dyiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="fh8h2dyiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:car-dealer" /></template>
