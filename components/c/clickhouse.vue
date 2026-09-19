<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohc817x8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ohc817x8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:clickhouse" /></template>
