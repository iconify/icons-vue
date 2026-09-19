<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o403b6bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o403b6bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:magnifying-glass" /></template>
