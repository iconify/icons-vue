<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/docpr_fdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="docpr_fdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-down-20-bold" /></template>
