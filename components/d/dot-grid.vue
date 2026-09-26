<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esxp_4pyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="esxp_4pyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:dot-grid" /></template>
