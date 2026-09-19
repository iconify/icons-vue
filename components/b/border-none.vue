<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej1okobup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ej1okobup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:border-none" /></template>
