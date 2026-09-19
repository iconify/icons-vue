<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwfiues2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwfiues2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:flag-1" /></template>
