<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tusap453n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tusap453n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:area-range-solid" /></template>
