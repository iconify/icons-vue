<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6u974y3x.css';
import '../../css/a/a19ub-b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="g6u974y3x"/><path class="a19ub-b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:globe-share" /></template>
