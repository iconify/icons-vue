<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyeaw4bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="hyeaw4bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:dentist" /></template>
