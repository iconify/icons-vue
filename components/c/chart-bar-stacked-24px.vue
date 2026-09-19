<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_p0p0b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_p0p0b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-bar-stacked-24px" /></template>
