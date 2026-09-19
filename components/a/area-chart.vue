<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osbn5umaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<path class="osbn5umaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:area-chart" /></template>
