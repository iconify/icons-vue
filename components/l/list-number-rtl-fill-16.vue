<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1g175bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m1g175bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:list-number-rtl-fill-16" /></template>
