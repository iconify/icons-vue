<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq0i1mbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zq0i1mbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:magnify-map" /></template>
