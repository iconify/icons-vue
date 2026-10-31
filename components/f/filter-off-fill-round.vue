<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da2l9qb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da2l9qb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:filter-off-fill-round" /></template>
