<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu6h595dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lu6h595dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-right-fill-16" /></template>
