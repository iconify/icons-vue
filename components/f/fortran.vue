<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4mjii14v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h4mjii14v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:fortran" /></template>
