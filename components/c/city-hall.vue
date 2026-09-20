<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q42marync.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="q42marync"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:city-hall" /></template>
