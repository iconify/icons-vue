<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io9_9gbtr.css';
import '../../css/k/koafcjh_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="io9_9gbtr"/><path class="koafcjh_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:excaliself" /></template>
