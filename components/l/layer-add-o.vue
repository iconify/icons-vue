<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2m-lcscl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="k2m-lcscl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-add-o" /></template>
