<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icxipw0ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="icxipw0ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:book-atlas" /></template>
