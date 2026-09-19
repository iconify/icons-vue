<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgebjd7_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgebjd7_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:house-01" /></template>
