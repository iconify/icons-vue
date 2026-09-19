<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzaqxznce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mzaqxznce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gradle-wordmark" /></template>
