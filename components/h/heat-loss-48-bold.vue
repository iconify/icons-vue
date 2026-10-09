<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv6cn3b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iv6cn3b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-loss-48-bold" /></template>
