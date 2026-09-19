<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf30sijas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lf30sijas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-drizzle-fill" /></template>
