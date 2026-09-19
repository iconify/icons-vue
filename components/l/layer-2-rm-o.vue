<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bda_-iejr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bda_-iejr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-2-rm-o" /></template>
