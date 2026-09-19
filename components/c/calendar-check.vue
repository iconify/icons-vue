<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiwps3bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="aiwps3bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:calendar-check" /></template>
