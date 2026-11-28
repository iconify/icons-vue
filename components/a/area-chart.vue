<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb4_doy5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb4_doy5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:area-chart" /></template>
