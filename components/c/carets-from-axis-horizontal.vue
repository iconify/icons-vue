<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp839kwkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp839kwkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:carets-from-axis-horizontal" /></template>
