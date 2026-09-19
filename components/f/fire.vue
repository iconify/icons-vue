<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3i702ico.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w3i702ico"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:fire" /></template>
