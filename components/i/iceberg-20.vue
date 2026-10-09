<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4tp--b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g4tp--b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:iceberg-20" /></template>
