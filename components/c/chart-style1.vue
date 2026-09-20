<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3mqsdxzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="k3mqsdxzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:chart-style1" /></template>
