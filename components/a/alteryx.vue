<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aazs-57qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":800};
const content = `<path class="aazs-57qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:alteryx" /></template>
