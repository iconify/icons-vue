<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db443pbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="db443pbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-right-20-bold" /></template>
