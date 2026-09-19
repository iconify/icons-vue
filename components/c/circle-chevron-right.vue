<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6l5w6gsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6l5w6gsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:circle-chevron-right" /></template>
