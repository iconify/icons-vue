<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu1u67bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":850};
const content = `<path class="eu1u67bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:linkedin" /></template>
