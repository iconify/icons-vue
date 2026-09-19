<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdm4mjb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jdm4mjb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-up-stroke-16" /></template>
