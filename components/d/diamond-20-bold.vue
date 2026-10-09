<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owp_lw21b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="owp_lw21b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:diamond-20-bold" /></template>
