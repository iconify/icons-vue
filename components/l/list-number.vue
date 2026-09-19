<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx3iejahs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="mx3iejahs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:list-number" /></template>
