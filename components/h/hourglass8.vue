<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g30le_0ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="g30le_0ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hourglass8" /></template>
