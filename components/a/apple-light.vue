<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc-1-6brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":814,"height":1000};
const content = `<path class="nc-1-6brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apple-light" /></template>
