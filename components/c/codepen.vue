<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehr3fswqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":988,"height":1000};
const content = `<path class="ehr3fswqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:codepen" /></template>
