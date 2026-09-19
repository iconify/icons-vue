<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2o0b988h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n2o0b988h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chart-mixed-dollar-solid" /></template>
