<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgyqsybdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="xgyqsybdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:direction" /></template>
