<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx_c6ibit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jx_c6ibit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:connect" /></template>
