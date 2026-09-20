<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvkrcr_dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fvkrcr_dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bee" /></template>
