<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlan15w3z.css';
import '../../css/g/ghlqhy24c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rlan15w3z"/><path class="ghlqhy24c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:graph" /></template>
