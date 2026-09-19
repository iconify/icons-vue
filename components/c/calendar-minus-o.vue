<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mag9m6fqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="mag9m6fqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:calendar-minus-o" /></template>
