<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud354hdiy.css';
import '../../css/f/fdn9dkb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ud354hdiy"/><path class="fdn9dkb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brain-20-bold" /></template>
