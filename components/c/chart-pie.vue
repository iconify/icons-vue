<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi16_abqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gi16_abqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:chart-pie" /></template>
