<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6sva07xu.css';
import '../../css/v/vt3tbsbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h6sva07xu"/><path class="vt3tbsbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hanger-20-bold" /></template>
