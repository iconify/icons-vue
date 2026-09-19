<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut17l-b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ut17l-b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:lightning-in-circle" /></template>
