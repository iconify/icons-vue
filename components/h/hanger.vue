<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du3nr_bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du3nr_bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hanger" /></template>
