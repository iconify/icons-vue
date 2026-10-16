<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqgqpt0as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gqgqpt0as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:centrifuge-20" /></template>
