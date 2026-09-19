<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kldiywb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":460,"height":512};
const content = `<path class="kldiywb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:leaflet" /></template>
