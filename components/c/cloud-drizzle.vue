<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efv6cdc0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="efv6cdc0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-drizzle" /></template>
