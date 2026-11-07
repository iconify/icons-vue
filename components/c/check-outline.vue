<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4osr_8qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4osr_8qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:check-outline" /></template>
