<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5ytazb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="h5ytazb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:earth-pacific-o" /></template>
