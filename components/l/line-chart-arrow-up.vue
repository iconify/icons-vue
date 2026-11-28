<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmspdxbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmspdxbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:line-chart-arrow-up" /></template>
