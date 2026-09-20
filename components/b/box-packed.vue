<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1icyubch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t1icyubch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:box-packed" /></template>
