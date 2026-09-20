<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwuf2jxfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":400};
const content = `<path class="mwuf2jxfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ibm" /></template>
