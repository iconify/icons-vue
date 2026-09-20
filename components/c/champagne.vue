<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w49qc5hpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="w49qc5hpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:champagne" /></template>
