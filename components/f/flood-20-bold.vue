<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enxooqysn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="enxooqysn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flood-20-bold" /></template>
