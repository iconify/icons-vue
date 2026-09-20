<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6-_wpxjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6-_wpxjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:clickhouse" /></template>
