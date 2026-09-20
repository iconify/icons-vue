<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek_n8cbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ek_n8cbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:cut" /></template>
