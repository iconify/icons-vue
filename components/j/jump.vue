<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi9w2m9_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="oi9w2m9_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:jump" /></template>
