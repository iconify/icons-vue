<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9fwjzi_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m9fwjzi_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:chart-area-fill" /></template>
