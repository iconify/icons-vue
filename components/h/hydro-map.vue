<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghf9evaie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ghf9evaie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:hydro-map" /></template>
