<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrkco2-xc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vrkco2-xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:copy" /></template>
