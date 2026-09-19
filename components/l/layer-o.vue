<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj0k-5wrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="tj0k-5wrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-o" /></template>
