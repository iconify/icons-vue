<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttc7fgbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ttc7fgbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:compass-rose" /></template>
