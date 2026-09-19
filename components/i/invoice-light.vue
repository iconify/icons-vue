<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjdxzzbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjdxzzbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:invoice-light" /></template>
