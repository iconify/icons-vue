<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdh42-b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rdh42-b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:list-number-rtl-fill-12" /></template>
