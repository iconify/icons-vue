<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyo1fpb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zyo1fpb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:flight-landing" /></template>
