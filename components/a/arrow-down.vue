<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab62mr4_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ab62mr4_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-down" /></template>
