<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hse_63wgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hse_63wgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:airport" /></template>
