<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq-_58_ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uq-_58_ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:angle-up" /></template>
