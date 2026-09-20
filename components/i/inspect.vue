<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff8z4qb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ff8z4qb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:inspect" /></template>
