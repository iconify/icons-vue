<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv1hvdbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fv1hvdbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:column-dependency" /></template>
