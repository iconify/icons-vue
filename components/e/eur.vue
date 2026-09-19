<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6qp5mb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o6qp5mb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:eur" /></template>
