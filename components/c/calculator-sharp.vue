<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgg8k3bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lgg8k3bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:calculator-sharp" /></template>
