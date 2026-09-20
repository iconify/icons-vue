<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm3bjm3aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rm3bjm3aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:connector-chart" /></template>
