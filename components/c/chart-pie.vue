<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx8wwcc3r.css';
import '../../css/m/mb8xl_g2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nx8wwcc3r"/><path class="mb8xl_g2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chart-pie" /></template>
