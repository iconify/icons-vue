<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q284ii8xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q284ii8xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:dbt" /></template>
