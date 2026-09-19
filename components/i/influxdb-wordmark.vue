<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeiup5blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="eeiup5blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:influxdb-wordmark" /></template>
