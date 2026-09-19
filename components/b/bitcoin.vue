<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef_mojbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ef_mojbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:bitcoin" /></template>
