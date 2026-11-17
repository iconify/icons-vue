<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeq8zv5rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeq8zv5rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chevrons-to-axis-horizontal" /></template>
