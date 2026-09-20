<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmw2_n2yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fmw2_n2yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:japan-police-station" /></template>
