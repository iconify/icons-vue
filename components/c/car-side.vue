<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_iz-6pyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j_iz-6pyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:car-side" /></template>
