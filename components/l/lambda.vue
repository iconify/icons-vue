<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m90omkbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="m90omkbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:lambda" /></template>
