<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6umq1pek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="w6umq1pek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:angle-double-right" /></template>
