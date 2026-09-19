<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnw9xub1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mnw9xub1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-error-bar" /></template>
