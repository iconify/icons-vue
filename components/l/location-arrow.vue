<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liws21bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="liws21bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:location-arrow" /></template>
