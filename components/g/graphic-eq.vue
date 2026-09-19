<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdjyulb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="vdjyulb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:graphic-eq" /></template>
