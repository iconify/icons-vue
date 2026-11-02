<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml6p7i4lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml6p7i4lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-lira-2-line" /></template>
