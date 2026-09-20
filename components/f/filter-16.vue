<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-74kyb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h-74kyb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:filter-16" /></template>
